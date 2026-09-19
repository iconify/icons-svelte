<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrb64pzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bbrb64pzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-cyrillic-filled" {...props}></Icon>
