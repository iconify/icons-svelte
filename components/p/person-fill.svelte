<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2p3z00al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f2p3z00al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-fill" {...props}></Icon>
