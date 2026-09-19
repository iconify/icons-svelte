<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mstr9jbxl.css';
import '../../css/d/dtz_ylbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer mstr9jbxl"/><path class="dtz_ylbin duoicon-secondary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bug" {...props}></Icon>
