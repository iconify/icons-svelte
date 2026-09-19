<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrwg9d6kl.css';
import '../../css/e/eqy7e86_g.css';
import '../../css/n/nuc11qh6t.css';
import '../../css/w/w-9yqheju.css';
import '../../css/n/ncbouabcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zrwg9d6kl"/><path class="eqy7e86_g"/><path class="nuc11qh6t"/><path class="w-9yqheju"/><path class="ncbouabcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nhibernate-wordmark" {...props}></Icon>
