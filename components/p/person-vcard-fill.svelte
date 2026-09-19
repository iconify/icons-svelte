<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqq74hb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vqq74hb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-vcard-fill" {...props}></Icon>
