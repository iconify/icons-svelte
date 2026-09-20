<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_c67094d.css';
import '../../css/j/jpl6uh7_x.css';
import '../../css/d/dtfn2kbod.css';
import '../../css/a/afxb8ccpm.css';
import '../../css/p/pw4ju4b7d.css';
import '../../css/s/se6g41bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_c67094d"/><path clip-rule="evenodd" class="jpl6uh7_x"/><path class="dtfn2kbod"/><path class="afxb8ccpm"/><path class="pw4ju4b7d"/><path class="se6g41bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:1inch" {...props}></Icon>
