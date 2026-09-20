<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/ljbdk7b8o.css';
import '../../css/g/g8b7pyjyq.css';
import '../../css/p/p-3pv-dez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ljbdk7b8o"/><circle class="g8b7pyjyq"/><circle class="p-3pv-dez"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-branch" {...props}></Icon>
