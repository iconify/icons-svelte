<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vifuy2dbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vifuy2dbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flash2-filled" {...props}></Icon>
