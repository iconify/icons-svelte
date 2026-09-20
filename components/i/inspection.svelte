<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob0xyledb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ob0xyledb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:inspection" {...props}></Icon>
