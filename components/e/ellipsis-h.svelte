<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty_ooxbvp.css';
import '../../css/f/ffappobrr.css';
import '../../css/u/uzprxqbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="ty_ooxbvp"/><circle class="ffappobrr"/><circle class="uzprxqbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:ellipsis-h" {...props}></Icon>
