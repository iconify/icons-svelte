<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy28hvb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy28hvb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codenewbie" {...props}></Icon>
