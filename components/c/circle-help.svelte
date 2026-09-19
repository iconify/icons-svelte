<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au3304bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au3304bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:circle-help" {...props}></Icon>
