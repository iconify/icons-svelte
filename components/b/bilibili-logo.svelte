<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bn9ma7box.css';
import '../../css/u/u6ect5bic.css';
import '../../css/w/w3051s3ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn9ma7box"/><path class="u6ect5bic"/><path class="w3051s3ye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bilibili-logo" {...props}></Icon>
