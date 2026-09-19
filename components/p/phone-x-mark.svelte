<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/effyh-lne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="effyh-lne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone-x-mark" {...props}></Icon>
