<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo1ge9bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vo1ge9bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-slash-16-solid" {...props}></Icon>
