<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2cki_7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="co2cki_7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-badge-minus-fill" {...props}></Icon>
