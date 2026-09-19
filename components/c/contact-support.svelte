<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exleob20c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="exleob20c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contact-support" {...props}></Icon>
