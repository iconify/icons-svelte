<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyureyb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyureyb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:adjustments" {...props}></Icon>
