<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5y77qbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v5y77qbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:coupling-facility-encryption" {...props}></Icon>
