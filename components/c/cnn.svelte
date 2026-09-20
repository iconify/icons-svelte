<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmtx4eb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmtx4eb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cnn" {...props}></Icon>
