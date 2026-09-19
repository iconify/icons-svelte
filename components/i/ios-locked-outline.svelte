<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fao0odb7l.css';
import '../../css/v/v-qvd4btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fao0odb7l"/><path class="v-qvd4btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-locked-outline" {...props}></Icon>
