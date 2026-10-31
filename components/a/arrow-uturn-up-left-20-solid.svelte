<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8n6e4yxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8n6e4yxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-up-left-20-solid" {...props}></Icon>
