<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvuddt06t.css';
import '../../css/x/x7k78fe0i.css';
import '../../css/i/iskyp3sfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvuddt06t"/><path class="x7k78fe0i"/><path class="iskyp3sfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:colab-google" {...props}></Icon>
