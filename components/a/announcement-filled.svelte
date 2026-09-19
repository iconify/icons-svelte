<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yypen4wvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yypen4wvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:announcement-filled" {...props}></Icon>
