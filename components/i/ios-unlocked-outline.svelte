<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-qvd4btd.css';
import '../../css/i/izm7r3btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v-qvd4btd"/><path class="izm7r3btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-unlocked-outline" {...props}></Icon>
