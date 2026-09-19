<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmuk_416i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bmuk_416i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-4-clubs" {...props}></Icon>
