<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysk3uyb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ysk3uyb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oral-contraception-pillsx21" {...props}></Icon>
