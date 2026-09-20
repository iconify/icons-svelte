<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eic95nb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eic95nb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-square-one-solid" {...props}></Icon>
