<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5p51vbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5p51vbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:podcastindex" {...props}></Icon>
