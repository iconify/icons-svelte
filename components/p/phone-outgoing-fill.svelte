<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8ofd0bhe.css';
import '../../css/m/m4slzdbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ofd0bhe"/><path class="m4slzdbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-outgoing-fill" {...props}></Icon>
