<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j855_w7iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j855_w7iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3-solid" {...props}></Icon>
