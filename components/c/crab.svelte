<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfa1bh-8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfa1bh-8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:crab" {...props}></Icon>
