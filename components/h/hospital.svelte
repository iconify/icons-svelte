<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma0t_dbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ma0t_dbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hospital" {...props}></Icon>
