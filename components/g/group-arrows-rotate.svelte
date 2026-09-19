<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iii9krbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="iii9krbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:group-arrows-rotate" {...props}></Icon>
