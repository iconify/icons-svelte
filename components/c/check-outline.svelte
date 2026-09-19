<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yes38jbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="check-outline"><path class="Vector yes38jbxi" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:check-outline" {...props}></Icon>
