<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8xj8r15t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8xj8r15t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-edit" {...props}></Icon>
