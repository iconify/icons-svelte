<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8rei_4_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8rei_4_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-minus" {...props}></Icon>
