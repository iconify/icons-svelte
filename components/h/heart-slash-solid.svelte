<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eilcihlxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eilcihlxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heart-slash-solid" {...props}></Icon>
