<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99tz67ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t99tz67ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:postgresql-fill" {...props}></Icon>
