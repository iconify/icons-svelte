<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvoy5jbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pvoy5jbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:colors-filled" {...props}></Icon>
