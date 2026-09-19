<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwjv8hipc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zwjv8hipc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:american-sign-language-outline" {...props}></Icon>
