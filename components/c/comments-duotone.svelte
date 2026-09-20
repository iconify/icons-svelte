<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xer9j-beb.css';
import '../../css/o/otnxsdo2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xer9j-beb"/><path clip-rule="evenodd" class="otnxsdo2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:comments-duotone" {...props}></Icon>
