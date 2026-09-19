<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv7i-tbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iv7i-tbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-one-small-filled" {...props}></Icon>
