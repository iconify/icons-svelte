<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/husm8abss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="husm8abss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:address-book-small" {...props}></Icon>
