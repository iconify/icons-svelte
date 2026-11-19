<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9q0bq0rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9q0bq0rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:energy-kwh" {...props}></Icon>
