<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivs71aced.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivs71aced"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:at-symbol" {...props}></Icon>
