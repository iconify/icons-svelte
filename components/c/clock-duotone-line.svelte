<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q-fwvxbba.css';
import '../../css/j/jkgvhzbvu.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGabB7geOy"><g class="ft5dv1b6b"><circle class="q-fwvxbba"/><path class="jkgvhzbvu"/></g></mask></defs><path mask="url(#SVGabB7geOy)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:clock-duotone-line" {...props}></Icon>
