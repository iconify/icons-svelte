<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q0nlyobyz.css';
import '../../css/e/e4xck0bwa.css';
import '../../css/i/ialavsbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q0nlyobyz"/><path class="e4xck0bwa"/><path class="ialavsbqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:presentation-02" {...props}></Icon>
