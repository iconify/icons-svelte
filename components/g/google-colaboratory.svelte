<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gavkigb0a.css';
import '../../css/j/j3mso-bst.css';
import '../../css/i/i7xxw6b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g display="block"><path class="gavkigb0a"/><path class="j3mso-bst"/><path class="i7xxw6b4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-colaboratory" {...props}></Icon>
