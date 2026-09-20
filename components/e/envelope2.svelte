<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkh17iapw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkh17iapw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope2" {...props}></Icon>
