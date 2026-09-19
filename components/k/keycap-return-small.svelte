<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o66p27q8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o66p27q8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-return-small" {...props}></Icon>
