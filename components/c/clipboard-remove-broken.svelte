<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/my5268blj.css';
import '../../css/c/c7hfprbvc.css';
import '../../css/n/ndq0ugbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="my5268blj"/><path class="c7hfprbvc"/><path class="ndq0ugbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-remove-broken" {...props}></Icon>
