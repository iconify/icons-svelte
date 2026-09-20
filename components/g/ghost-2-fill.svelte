<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8psnb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq8psnb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-2-fill" {...props}></Icon>
