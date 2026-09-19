<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obit9z1kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obit9z1kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:cake" {...props}></Icon>
