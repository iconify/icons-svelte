<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l907abc-p.css';
import '../../css/g/gitf0_yii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l907abc-p"/><path class="gitf0_yii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:error-duotone" {...props}></Icon>
