<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1ywzv1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md1ywzv1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bem" {...props}></Icon>
