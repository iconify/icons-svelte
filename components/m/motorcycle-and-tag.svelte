<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og-moc5vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="og-moc5vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-tag" {...props}></Icon>
