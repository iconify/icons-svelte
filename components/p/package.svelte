<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaa6_29ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaa6_29ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:package" {...props}></Icon>
