<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz1je_b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sz1je_b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:github-one" {...props}></Icon>
