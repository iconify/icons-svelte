<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v21p3mbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v21p3mbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bnbchain" {...props}></Icon>
