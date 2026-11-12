<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kaad2k6uy.css';
import '../../css/z/zvcyosrjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kaad2k6uy"/><path class="zvcyosrjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planka-dark" {...props}></Icon>
