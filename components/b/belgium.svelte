<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb8-7u1lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kb8-7u1lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:belgium" {...props}></Icon>
