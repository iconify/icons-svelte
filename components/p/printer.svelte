<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v88vjybly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v88vjybly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:printer" {...props}></Icon>
