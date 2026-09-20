<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yupezqv6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yupezqv6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:material-for-mkdocs" {...props}></Icon>
