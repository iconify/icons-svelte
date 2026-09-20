<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaok-xlkj.css';
import '../../css/h/h5ggh0boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kaok-xlkj"/><path class="h5ggh0boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:key-skeleton" {...props}></Icon>
