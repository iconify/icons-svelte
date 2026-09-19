<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8osg5fzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j8osg5fzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-hwid-small-filled" {...props}></Icon>
