<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o34222bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o34222bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-2-fill" {...props}></Icon>
