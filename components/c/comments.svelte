<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqnw9gbzk.css';
import '../../css/v/vzxnh3iad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqnw9gbzk"/><path class="vzxnh3iad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:comments" {...props}></Icon>
