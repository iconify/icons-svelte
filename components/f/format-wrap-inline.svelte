<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9aox44tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9aox44tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-wrap-inline" {...props}></Icon>
