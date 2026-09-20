<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl33b-fvk.css';
import '../../css/o/o6kz01jke.css';
import '../../css/o/oxyodjyqf.css';
import '../../css/g/g16ecdgti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yl33b-fvk"/><path class="o6kz01jke"/><path class="oxyodjyqf"/><path class="g16ecdgti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aliexpress" {...props}></Icon>
