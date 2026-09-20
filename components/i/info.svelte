<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/axarcbb2r.css';
import '../../css/w/wp23mgbqq.css';
import '../../css/f/fqg7gacch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="axarcbb2r"/><path class="wp23mgbqq"/><circle class="fqg7gacch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:info" {...props}></Icon>
