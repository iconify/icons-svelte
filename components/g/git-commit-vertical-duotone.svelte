<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-8qs0b7j.css';
import '../../css/j/jyuddqs9y.css';
import '../../css/o/ouonzyb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h-8qs0b7j"/><path class="jyuddqs9y"/><path class="ouonzyb1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:git-commit-vertical-duotone" {...props}></Icon>
