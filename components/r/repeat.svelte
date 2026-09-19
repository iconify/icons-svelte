<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s76artdks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s76artdks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:repeat" {...props}></Icon>
