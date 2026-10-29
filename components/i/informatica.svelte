<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuw36nbvq.css';
import '../../css/f/fq-4mcc3f.css';
import '../../css/g/gx7tam2pd.css';
import '../../css/j/jcnnhfisw.css';
import '../../css/z/zqsxmxbqb.css';
import '../../css/f/f8yuy4b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iuw36nbvq"/><path class="fq-4mcc3f"/><path class="gx7tam2pd"/><path class="jcnnhfisw"/><path class="zqsxmxbqb"/><path class="f8yuy4b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:informatica" {...props}></Icon>
