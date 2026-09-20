<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6khx287g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6khx287g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-2-check" {...props}></Icon>
