<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjc8iehpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjc8iehpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parenthesis-right-solid" {...props}></Icon>
