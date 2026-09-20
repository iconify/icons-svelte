<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9jqkibzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9jqkibzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:builtbybit" {...props}></Icon>
