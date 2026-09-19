<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p93lfi37p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p93lfi37p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:face-smile" {...props}></Icon>
