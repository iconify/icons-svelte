<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-lvl5b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-lvl5b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dice-one" {...props}></Icon>
