<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhcjeybja.css';
import '../../css/o/o9ffdfb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="dhcjeybja"/><path class="o9ffdfb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:pe-4x3" {...props}></Icon>
