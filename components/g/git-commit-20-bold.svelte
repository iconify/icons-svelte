<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wopchbcny.css';
import '../../css/w/wjqe3kpku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wopchbcny"/><path class="wjqe3kpku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-commit-20-bold" {...props}></Icon>
