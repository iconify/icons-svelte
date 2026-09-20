<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-acbdc4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-acbdc4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-open-solid" {...props}></Icon>
