<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9w90ebru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-10-sharp-fill" {...props}></Icon>
<style>
:global(.y9w90ebru) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM11 5L11 10.2679L7.6699 8.3455L6.6699 10.0775L11.5 12.8662C12.1666 13.2512 13 12.77 13 12.0002L13 5L11 5Z");
}

</style>
