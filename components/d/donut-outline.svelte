<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8gd2ib8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8gd2ib8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:donut-outline" {...props}></Icon>
