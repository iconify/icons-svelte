<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idqc4jb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idqc4jb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dot-radiowaves-circle-solid" {...props}></Icon>
