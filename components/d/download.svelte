<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giq5sk66w.css';
import '../../css/y/yypjo3b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="giq5sk66w"/><path class="yypjo3b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:download" {...props}></Icon>
