<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3p24nbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3p24nbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:building-storefront" {...props}></Icon>
