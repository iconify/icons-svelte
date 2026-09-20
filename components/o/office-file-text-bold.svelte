<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zemhzbc5a.css';
import '../../css/r/r6fwiknyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zemhzbc5a"/><path class="r6fwiknyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-file-text-bold" {...props}></Icon>
