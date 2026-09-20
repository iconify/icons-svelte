<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn2e4nb2l.css';
import '../../css/t/tr3-hqbzp.css';
import '../../css/z/z9_diac_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gn2e4nb2l"/><path class="tr3-hqbzp"/><path class="z9_diac_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nbt" {...props}></Icon>
