<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vjlo9pbii.css';
import '../../css/t/tsag75lsy.css';
import '../../css/n/nx5xs9buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vjlo9pbii"/><path clip-rule="evenodd" class="tsag75lsy"/><path clip-rule="evenodd" class="nx5xs9buk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-outline" {...props}></Icon>
