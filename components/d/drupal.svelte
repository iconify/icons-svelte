<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2cxhrb1t.css';
import '../../css/z/zjuzcpbhe.css';
import '../../css/a/ayo620-7m.css';
import '../../css/h/h6gdwbeok.css';
import '../../css/b/br579xj1y.css';
import '../../css/r/r83crp8zv.css';
import '../../css/o/omnphvblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q2cxhrb1t"/><path class="zjuzcpbhe"/><path class="ayo620-7m"/><path class="h6gdwbeok"/><path class="br579xj1y"/><path class="r83crp8zv"/><path class="omnphvblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:drupal" {...props}></Icon>
