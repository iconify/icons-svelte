<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1xy6nh9u.css';
import '../../css/b/b8gjdvb7r.css';
import '../../css/h/hux66ibbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><path class="b8gjdvb7r"/><path class="hux66ibbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-station" {...props}></Icon>
