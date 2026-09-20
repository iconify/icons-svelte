<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9jcp6bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="q9jcp6bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:invisible" {...props}></Icon>
