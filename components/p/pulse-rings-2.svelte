<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm2moacxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path transform="matrix(0 0 0 0 12 12)" class="lm2moacxj"><animateTransform id="SVGk7g6Ie5D" attributeName="transform" begin="0;SVGADuEYsSK.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" type="translate" values="12 12;0 0"/><animateTransform additive="sum" attributeName="transform" begin="0;SVGADuEYsSK.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" type="scale" values="0;1"/><animate attributeName="opacity" begin="0;SVGADuEYsSK.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="1;0"/></path><path transform="matrix(0 0 0 0 12 12)" class="lm2moacxj"><animateTransform id="SVGADuEYsSK" attributeName="transform" begin="SVGk7g6Ie5D.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" type="translate" values="12 12;0 0"/><animateTransform additive="sum" attributeName="transform" begin="SVGk7g6Ie5D.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" type="scale" values="0;1"/><animate attributeName="opacity" begin="SVGk7g6Ie5D.begin+0.6s" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" values="1;0"/></path>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="svg-spinners:pulse-rings-2" {...props}></Icon>
