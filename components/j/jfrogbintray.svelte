<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bol0cqe0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bol0cqe0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jfrogbintray" {...props}></Icon>
