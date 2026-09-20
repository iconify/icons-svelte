<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tts06v5dt.css';
import '../../css/o/o27tr5bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tts06v5dt"/><path class="o27tr5bta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-vert-duotone" {...props}></Icon>
