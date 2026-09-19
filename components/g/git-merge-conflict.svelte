<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csnu-zy4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csnu-zy4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-merge-conflict" {...props}></Icon>
