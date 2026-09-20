<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8f3qv90t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8f3qv90t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:octagon" {...props}></Icon>
