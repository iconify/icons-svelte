<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msz6qd2fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msz6qd2fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-indent-decrease" {...props}></Icon>
