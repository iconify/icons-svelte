<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqzh37bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oqzh37bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:android-alt" {...props}></Icon>
