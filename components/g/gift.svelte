<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7fzjqbhc.css';
import '../../css/d/drnzv18qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7fzjqbhc"/><path class="drnzv18qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:gift" {...props}></Icon>
