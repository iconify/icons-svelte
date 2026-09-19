<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xca2aubva.css';
import '../../css/o/on_40xtwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer xca2aubva"/><path class="duoicon-secondary-layer on_40xtwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:brush-2" {...props}></Icon>
