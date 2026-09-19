<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kly8rpblu.css';
import '../../css/o/on39wybyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer kly8rpblu"/><path class="duoicon-primary-layer on39wybyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:clipboard" {...props}></Icon>
